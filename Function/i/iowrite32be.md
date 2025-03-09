# Function: <code>iowrite32be</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583050528,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:128",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583050528,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583344048,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:128",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583344048,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583469424,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:128",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583469424,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583491664,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:128",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583491664,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583672704,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:129",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583672704,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583890480,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:129",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583890480,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583974720,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:129",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583974720,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 55
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584157136,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584157136,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584290880,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584290880,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584701616,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584701616,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584814912,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584814912,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584859472,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584859472,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585280928,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585280928,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 79
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586132752,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/gpio/gpio-mmio.c:bgpio_write32be",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586132752,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587123792,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:227",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/gpio/gpio-mmio.c:bgpio_write32be",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587123792,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587386000,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:227",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/gpio/gpio-mmio.c:bgpio_write32be",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587386000,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587720352,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:227",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/gpio/gpio-mmio.c:bgpio_write32be",
        "drivers/pci/quirks.c:reset_hinic_vf_dev",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_setup_port",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_rs485_config",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_iowrite32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587720352,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 126
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055290442304,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/gpio/gpio-mmio.c:bgpio_write32be",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290442304,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "iowrite32be",
  "collision_type": "Static Duplication",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271748286,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "kernel/irq/generic-chip.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "kernel/irq/generic-chip.c:irq_writel_be"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275505020,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/gpio/gpio-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/gpio/gpio-mmio.c:bgpio_write32be"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275912832,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/clk/clk-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-divider.c:clk_divider_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275917638,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/clk/clk-gate.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-gate.c:clk_gate_endisable"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275918576,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/clk/clk-multiplier.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275919490,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/clk/clk-mux.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-mux.c:clk_mux_set_parent"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936275922946,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/clk/clk-fractional-divider.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276174420,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/tty/serial/8250/8250_port.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276191980,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/tty/serial/8250/8250_dwlib.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276207804,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/tty/serial/8250/8250_early.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936276480188,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/base/regmap/regmap-mmio.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ],
      "caller_func": []
    },
    {
      "addr": 18446743936277003888,
      "name": "iowrite32be",
      "external": false,
      "loc": "include/asm-generic/io.h:788",
      "file": "drivers/spi/spi-fsl-spi.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:of_fsl_spi_probe",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_grlib_cs_control",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_irq",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_do_one_msg",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode",
        "drivers/spi/spi-fsl-spi.c:fsl_spi_change_mode"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584259616,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/gpio/gpio-mmio.c:bgpio_write32be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584259616,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584194816,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584194816,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584243376,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584243376,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
void iowrite32be(u32 val, void * addr)
```

```json
{
  "name": "iowrite32be",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584348208,
      "name": "iowrite32be",
      "external": true,
      "loc": "lib/iomap.c:205",
      "file": "lib/iomap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/irq/generic-chip.c:irq_writel_be",
        "drivers/clk/clk-divider.c:clk_divider_set_rate",
        "drivers/clk/clk-gate.c:clk_gate_endisable",
        "drivers/clk/clk-multiplier.c:clk_multiplier_set_rate",
        "drivers/clk/clk-mux.c:clk_mux_set_parent",
        "drivers/clk/clk-fractional-divider.c:clk_fd_set_rate",
        "drivers/tty/serial/8250/8250_port.c:mem32be_serial_out",
        "drivers/tty/serial/8250/8250_dwlib.c:dw8250_set_divisor",
        "drivers/tty/serial/8250/8250_early.c:serial8250_early_out",
        "drivers/base/regmap/regmap-mmio.c:regmap_mmio_write32be"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584348208,
      "name": "iowrite32be",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 53
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void iowrite32be(u32 val, void * addr)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void iowrite32be(u32 val, void * addr)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void iowrite32be(u32 val, void * addr)
```
</details>
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
