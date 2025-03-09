# Function: <code>sx150x_write_cfg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
s32 sx150x_write_cfg(struct sx150x_chip * chip, u8 offset, u8 width, u8 reg, u8 val)
```

```json
{
  "name": "sx150x_write_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215200,
      "name": "sx150x_write_cfg",
      "external": false,
      "loc": "drivers/gpio/gpio-sx150x.c:225",
      "file": "drivers/gpio/gpio-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_set",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_direction_input"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215200,
      "name": "sx150x_write_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
s32 sx150x_write_cfg(struct sx150x_chip * chip, u8 offset, u8 width, u8 reg, u8 val)
```

```json
{
  "name": "sx150x_write_cfg",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522160,
      "name": "sx150x_write_cfg",
      "external": false,
      "loc": "drivers/gpio/gpio-sx150x.c:307",
      "file": "drivers/gpio/gpio-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_bus_sync_unlock",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_direction_output",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_direction_output",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_direction_input",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_set_single_ended",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_set_single_ended",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_set"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522160,
      "name": "sx150x_write_cfg",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 194
    }
  ]
}
```
</details>
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
s32 sx150x_write_cfg(struct sx150x_chip * chip, u8 offset, u8 width, u8 reg, u8 val)
```
</details>
</li>
</ul>
