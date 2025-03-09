# Function: <code>sx150x_i2c_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
s32 sx150x_i2c_write(struct i2c_client * client, u8 reg, u8 val)
```

```json
{
  "name": "sx150x_i2c_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583215104,
      "name": "sx150x_i2c_write",
      "external": false,
      "loc": "drivers/gpio/gpio-sx150x.c:168",
      "file": "drivers/gpio/gpio-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_write_cfg",
        "drivers/gpio/gpio-sx150x.c:sx150x_init_io",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_set",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583215104,
      "name": "sx150x_i2c_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
s32 sx150x_i2c_write(struct i2c_client * client, u8 reg, u8 val)
```

```json
{
  "name": "sx150x_i2c_write",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583522064,
      "name": "sx150x_i2c_write",
      "external": false,
      "loc": "drivers/gpio/gpio-sx150x.c:250",
      "file": "drivers/gpio/gpio-sx150x.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_probe",
        "drivers/gpio/gpio-sx150x.c:sx150x_init_io",
        "drivers/gpio/gpio-sx150x.c:sx150x_irq_thread_fn",
        "drivers/gpio/gpio-sx150x.c:sx150x_gpio_set",
        "drivers/gpio/gpio-sx150x.c:sx150x_write_cfg"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583522064,
      "name": "sx150x_i2c_write",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
s32 sx150x_i2c_write(struct i2c_client * client, u8 reg, u8 val)
```
</details>
</li>
</ul>
