# Function: <code>acpi_dev_power_state_for_wake</code>

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
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
u8 acpi_dev_power_state_for_wake(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_power_state_for_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588660448,
      "name": "acpi_dev_power_state_for_wake",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:494",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588660448,
      "name": "acpi_dev_power_state_for_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
u8 acpi_dev_power_state_for_wake(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_power_state_for_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588948432,
      "name": "acpi_dev_power_state_for_wake",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:494",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588948432,
      "name": "acpi_dev_power_state_for_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
u8 acpi_dev_power_state_for_wake(struct acpi_device * adev)
```

```json
{
  "name": "acpi_dev_power_state_for_wake",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589245056,
      "name": "acpi_dev_power_state_for_wake",
      "external": true,
      "loc": "drivers/acpi/device_pm.c:507",
      "file": "drivers/acpi/device_pm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3",
        "drivers/pci/pci-acpi.c:acpi_pci_bridge_d3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589245056,
      "name": "acpi_dev_power_state_for_wake",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 107
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
u8 acpi_dev_power_state_for_wake(struct acpi_device * adev)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
