# Function: <code>acpi_dev_clear_dependencies</code>

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
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_dev_clear_dependencies(struct acpi_device * supplier)
```

```json
{
  "name": "acpi_dev_clear_dependencies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586186560,
      "name": "acpi_dev_clear_dependencies",
      "external": true,
      "loc": "drivers/acpi/scan.c:2317",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586186560,
      "name": "acpi_dev_clear_dependencies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 101
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
void acpi_dev_clear_dependencies(struct acpi_device * supplier)
```

```json
{
  "name": "acpi_dev_clear_dependencies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587422416,
      "name": "acpi_dev_clear_dependencies",
      "external": true,
      "loc": "drivers/acpi/scan.c:2361",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587422416,
      "name": "acpi_dev_clear_dependencies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_dev_clear_dependencies(struct acpi_device * supplier)
```

```json
{
  "name": "acpi_dev_clear_dependencies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588679248,
      "name": "acpi_dev_clear_dependencies",
      "external": true,
      "loc": "drivers/acpi/scan.c:2358",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588679248,
      "name": "acpi_dev_clear_dependencies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_dev_clear_dependencies(struct acpi_device * supplier)
```

```json
{
  "name": "acpi_dev_clear_dependencies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588966992,
      "name": "acpi_dev_clear_dependencies",
      "external": true,
      "loc": "drivers/acpi/scan.c:2365",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588966992,
      "name": "acpi_dev_clear_dependencies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
void acpi_dev_clear_dependencies(struct acpi_device * supplier)
```

```json
{
  "name": "acpi_dev_clear_dependencies",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589264448,
      "name": "acpi_dev_clear_dependencies",
      "external": true,
      "loc": "drivers/acpi/scan.c:2398",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add",
        "drivers/acpi/ec.c:acpi_ec_add",
        "drivers/acpi/pmic/intel_pmic_chtdc_ti.c:chtdc_ti_pmic_opregion_probe",
        "drivers/i2c/i2c-core-acpi.c:i2c_acpi_register_devices"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589264448,
      "name": "acpi_dev_clear_dependencies",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 111
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void acpi_dev_clear_dependencies(struct acpi_device * supplier)
```
</details>
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
