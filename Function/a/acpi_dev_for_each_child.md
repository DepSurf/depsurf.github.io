# Function: <code>acpi_dev_for_each_child</code>

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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int acpi_dev_for_each_child(struct acpi_device * adev, int (*)(struct acpi_device *, void *) fn, void * data)
```

```json
{
  "name": "acpi_dev_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587413248,
      "name": "acpi_dev_for_each_child",
      "external": true,
      "loc": "drivers/acpi/bus.c:1105",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587413248,
      "name": "acpi_dev_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int acpi_dev_for_each_child(struct acpi_device * adev, int (*)(struct acpi_device *, void *) fn, void * data)
```

```json
{
  "name": "acpi_dev_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588665376,
      "name": "acpi_dev_for_each_child",
      "external": true,
      "loc": "drivers/acpi/bus.c:1105",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr",
        "drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended",
        "drivers/acpi/glue.c:acpi_find_child_by_adr",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/container.c:acpi_container_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588665376,
      "name": "acpi_dev_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int acpi_dev_for_each_child(struct acpi_device * adev, int (*)(struct acpi_device *, void *) fn, void * data)
```

```json
{
  "name": "acpi_dev_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588952640,
      "name": "acpi_dev_for_each_child",
      "external": true,
      "loc": "drivers/acpi/bus.c:1078",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr",
        "drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended",
        "drivers/acpi/glue.c:acpi_find_child_by_adr",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/container.c:acpi_container_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588952640,
      "name": "acpi_dev_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int acpi_dev_for_each_child(struct acpi_device * adev, int (*)(struct acpi_device *, void *) fn, void * data)
```

```json
{
  "name": "acpi_dev_for_each_child",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589249392,
      "name": "acpi_dev_for_each_child",
      "external": true,
      "loc": "drivers/acpi/bus.c:1130",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/device_pm.c:acpi_dev_power_up_children_with_adr",
        "drivers/acpi/device_pm.c:acpi_device_fix_up_power_children",
        "drivers/acpi/device_pm.c:acpi_device_fix_up_power_extended",
        "drivers/acpi/glue.c:acpi_find_child_by_adr",
        "drivers/acpi/glue.c:acpi_find_child_device",
        "drivers/acpi/glue.c:find_child_checks",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/scan.c:acpi_bus_attach",
        "drivers/acpi/property.c:acpi_get_next_subnode",
        "drivers/acpi/container.c:acpi_container_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589249392,
      "name": "acpi_dev_for_each_child",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 91
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
int acpi_dev_for_each_child(struct acpi_device * adev, int (*)(struct acpi_device *, void *) fn, void * data)
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
