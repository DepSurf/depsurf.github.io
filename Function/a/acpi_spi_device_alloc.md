# Function: <code>acpi_spi_device_alloc</code>

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
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
struct spi_device * acpi_spi_device_alloc(struct spi_controller * ctlr, struct acpi_device * adev, int index)
```

```json
{
  "name": "acpi_spi_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_spi_device_alloc",
      "external": true,
      "loc": "drivers/spi/spi.c:2460",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594419929,
      "name": "acpi_spi_device_alloc.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 49
    },
    {
      "addr": 18446744071589643264,
      "name": "acpi_spi_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 428
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
struct spi_device * acpi_spi_device_alloc(struct spi_controller * ctlr, struct acpi_device * adev, int index)
```

```json
{
  "name": "acpi_spi_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591252912,
      "name": "acpi_spi_device_alloc",
      "external": true,
      "loc": "drivers/spi/spi.c:2637",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591252912,
      "name": "acpi_spi_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
struct spi_device * acpi_spi_device_alloc(struct spi_controller * ctlr, struct acpi_device * adev, int index)
```

```json
{
  "name": "acpi_spi_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591605792,
      "name": "acpi_spi_device_alloc",
      "external": true,
      "loc": "drivers/spi/spi.c:2646",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591605792,
      "name": "acpi_spi_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 473
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
struct spi_device * acpi_spi_device_alloc(struct spi_controller * ctlr, struct acpi_device * adev, int index)
```

```json
{
  "name": "acpi_spi_device_alloc",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592337744,
      "name": "acpi_spi_device_alloc",
      "external": true,
      "loc": "drivers/spi/spi.c:2778",
      "file": "drivers/spi/spi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/spi/spi.c:acpi_register_spi_device"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592337744,
      "name": "acpi_spi_device_alloc",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 558
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
struct spi_device * acpi_spi_device_alloc(struct spi_controller * ctlr, struct acpi_device * adev, int index)
```
</details>
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
