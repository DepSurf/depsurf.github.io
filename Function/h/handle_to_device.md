# Function: <code>handle_to_device</code>

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
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * handle_to_device(acpi_handle handle, void (*)(void *) callback)
```

```json
{
  "name": "handle_to_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585707027,
      "name": "handle_to_device",
      "external": false,
      "loc": "drivers/acpi/scan.c:577",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device"
      ],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585703152,
      "name": "handle_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * handle_to_device(acpi_handle handle, void (*)(void *) callback)
```

```json
{
  "name": "handle_to_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586183664,
      "name": "handle_to_device",
      "external": false,
      "loc": "drivers/acpi/scan.c:574",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_dev_get_first_consumer_dev",
        "drivers/acpi/scan.c:acpi_scan_clear_dep",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586183664,
      "name": "handle_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * handle_to_device(acpi_handle handle, void (*)(void *) callback)
```

```json
{
  "name": "handle_to_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587419344,
      "name": "handle_to_device",
      "external": false,
      "loc": "drivers/acpi/scan.c:576",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_dev_get_first_consumer_dev",
        "drivers/acpi/scan.c:acpi_scan_clear_dep",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587419344,
      "name": "handle_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * handle_to_device(acpi_handle handle, void (*)(void *) callback)
```

```json
{
  "name": "handle_to_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588676176,
      "name": "handle_to_device",
      "external": false,
      "loc": "drivers/acpi/scan.c:568",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev",
        "drivers/acpi/scan.c:acpi_scan_clear_dep",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676176,
      "name": "handle_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * handle_to_device(acpi_handle handle, void (*)(void *) callback)
```

```json
{
  "name": "handle_to_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588963904,
      "name": "handle_to_device",
      "external": false,
      "loc": "drivers/acpi/scan.c:567",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev",
        "drivers/acpi/scan.c:acpi_scan_clear_dep",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588963904,
      "name": "handle_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
struct acpi_device * handle_to_device(acpi_handle handle, void (*)(void *) callback)
```

```json
{
  "name": "handle_to_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589261344,
      "name": "handle_to_device",
      "external": false,
      "loc": "drivers/acpi/scan.c:567",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_bus_scan",
        "drivers/acpi/scan.c:acpi_dev_get_next_consumer_dev",
        "drivers/acpi/scan.c:acpi_scan_clear_dep",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589261344,
      "name": "handle_to_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 142
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
struct acpi_device * handle_to_device(acpi_handle handle, void (*)(void *) callback)
```
</details>
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
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
