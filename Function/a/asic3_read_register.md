# Function: <code>asic3_read_register</code>

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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
u32 asic3_read_register(struct asic3 * asic, unsigned int reg)
```

```json
{
  "name": "asic3_read_register",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3231772332,
      "name": "asic3_read_register",
      "external": true,
      "loc": "drivers/mfd/asic3.c:97",
      "file": "drivers/mfd/asic3.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/mfd/asic3.c:asic3_clk_disable",
        "drivers/mfd/asic3.c:asic3_clk_enable",
        "drivers/mfd/asic3.c:asic3_gpio_set",
        "drivers/mfd/asic3.c:asic3_gpio_get",
        "drivers/mfd/asic3.c:asic3_gpio_direction",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_gpio_irq_type",
        "drivers/mfd/asic3.c:asic3_unmask_irq",
        "drivers/mfd/asic3.c:asic3_unmask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_mask_irq",
        "drivers/mfd/asic3.c:asic3_mask_gpio_irq",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_irq_demux",
        "drivers/mfd/asic3.c:asic3_set_register"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3231769016,
      "name": "asic3_read_register",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 48
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
u32 asic3_read_register(struct asic3 * asic, unsigned int reg)
```
</details>
</li>
</ul>
