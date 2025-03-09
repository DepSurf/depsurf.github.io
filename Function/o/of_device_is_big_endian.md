# Function: <code>of_device_is_big_endian</code>

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
bool of_device_is_big_endian(const struct device_node * device)
```

```json
{
  "name": "of_device_is_big_endian",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501596208,
      "name": "of_device_is_big_endian",
      "external": true,
      "loc": "drivers/of/base.c:668",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/tty/serial/8250/8250_dw.c:dw8250_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501596208,
      "name": "of_device_is_big_endian",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 64
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
bool of_device_is_big_endian(const struct device_node * device)
```

```json
{
  "name": "of_device_is_big_endian",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234121716,
      "name": "of_device_is_big_endian",
      "external": true,
      "loc": "drivers/of/base.c:668",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe",
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe",
        "drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234121716,
      "name": "of_device_is_big_endian",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
bool of_device_is_big_endian(const struct device_node * device)
```

```json
{
  "name": "of_device_is_big_endian",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295013968,
      "name": "of_device_is_big_endian",
      "external": true,
      "loc": "drivers/of/base.c:668",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295013968,
      "name": "of_device_is_big_endian",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 68
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
bool of_device_is_big_endian(const struct device_node * device)
```

```json
{
  "name": "of_device_is_big_endian",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278063952,
      "name": "of_device_is_big_endian",
      "external": true,
      "loc": "drivers/of/base.c:668",
      "file": "drivers/of/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpio-mmio.c:bgpio_pdev_probe"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278063952,
      "name": "of_device_is_big_endian",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 56
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
bool of_device_is_big_endian(const struct device_node * device)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
bool of_device_is_big_endian(const struct device_node * device)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
bool of_device_is_big_endian(const struct device_node * device)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
bool of_device_is_big_endian(const struct device_node * device)
```
</details>
</li>
</ul>
