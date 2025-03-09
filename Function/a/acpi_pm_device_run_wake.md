# Function: <code>acpi_pm_device_run_wake</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_pm_device_run_wake(struct device * phys_dev, bool enable)
```

```json
{
  "name": "acpi_pm_device_run_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583551725,
      "name": "acpi_pm_device_run_wake",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:723",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583551725,
      "name": "acpi_pm_device_run_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 119
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_pm_device_run_wake(struct device * phys_dev, bool enable)
```

```json
{
  "name": "acpi_pm_device_run_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583873187,
      "name": "acpi_pm_device_run_wake",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:725",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583873187,
      "name": "acpi_pm_device_run_wake",
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
<summary>In <code>4.10.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_pm_device_run_wake(struct device * phys_dev, bool enable)
```

```json
{
  "name": "acpi_pm_device_run_wake",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584012241,
      "name": "acpi_pm_device_run_wake",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:725",
      "file": "drivers/acpi/device_pm.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/ata/libata-zpodd.c:zpodd_disable_run_wake",
        "drivers/ata/libata-zpodd.c:zpodd_enable_run_wake"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584012241,
      "name": "acpi_pm_device_run_wake",
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int acpi_pm_device_run_wake(struct device * phys_dev, bool enable)
```
</details>
</li>
</ul>
