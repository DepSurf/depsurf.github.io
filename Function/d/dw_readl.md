# Function: <code>dw_readl</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586339813,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:67",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586339888,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586804277,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:67",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586804352,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587077621,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:68",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077792,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587237893,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587238064,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587504917,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587505216,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587708053,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708352,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
    }
  ]
}
```
</details>
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
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500873920,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500873920,
      "name": "dw_readl",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233382580,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233382824,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
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
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294335296,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294335296,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277666280,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277666280,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 128
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587664197,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664496,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```

```json
{
  "name": "dw_readl",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587770581,
      "name": "dw_readl",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:56",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_read_comp_param",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_wait_bus_not_busy",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_sda_hold",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_set_reg_access"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587770880,
      "name": "dw_readl",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<summary>Added between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➕</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```
</details>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
u32 dw_readl(struct dw_i2c_dev * dev, int offset)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
