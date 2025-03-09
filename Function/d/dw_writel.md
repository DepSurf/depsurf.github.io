# Function: <code>dw_writel</code>

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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586341157,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:83",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait"
      ],
      "caller_func": [
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
      "addr": 18446744071586339968,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586805621,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:83",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_enable_and_wait"
      ],
      "caller_func": [
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
      "addr": 18446744071586804432,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587079029,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:84",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587077872,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587239829,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_isr",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587238144,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 59
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587506757,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587505296,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587709893,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587708432,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500876112,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500874096,
      "name": "dw_writel",
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233384836,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-common.c:__i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233382908,
      "name": "dw_writel",
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294335760,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294335760,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277668198,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277666456,
      "name": "dw_writel",
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587666037,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587664576,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```

```json
{
  "name": "dw_writel",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587772421,
      "name": "dw_writel",
      "external": true,
      "loc": "drivers/i2c/busses/i2c-designware-common.c:72",
      "file": "drivers/i2c/busses/i2c-designware-common.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable_int",
        "drivers/i2c/busses/i2c-designware-common.c:i2c_dw_disable"
      ],
      "caller_func": [
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_irq_handler_master",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer",
        "drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587770960,
      "name": "dw_writel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 61
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
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
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void dw_writel(struct dw_i2c_dev * dev, u32 b, int offset)
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
