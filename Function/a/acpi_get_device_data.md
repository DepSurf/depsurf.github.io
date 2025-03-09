# Function: <code>acpi_get_device_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583560889,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:559",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_get_device",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583885581,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:579",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_get_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584024695,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:580",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_get_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584079430,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:578",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071584077728,
      "name": "acpi_get_device_data.constprop.15",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584346528,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:579",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584346528,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 166
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584567536,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:580",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584567536,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584665328,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:580",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584665328,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584865440,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:581",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865440,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585001312,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:581",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585001312,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585705738,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:580",
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
      "addr": 18446744071585701600,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585827914,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:580",
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
      "addr": 18446744071585823360,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 159
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336497414196,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:581",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446603336497412616,
      "name": "acpi_get_device_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584947446,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:581",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071584946096,
      "name": "acpi_get_device_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584856246,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:581",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
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
      "addr": 18446744071584854896,
      "name": "acpi_get_device_data.constprop.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071584952896,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:581",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584952896,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```

```json
{
  "name": "acpi_get_device_data",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071585059072,
      "name": "acpi_get_device_data",
      "external": false,
      "loc": "drivers/acpi/scan.c:581",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_init",
        "drivers/acpi/scan.c:acpi_walk_dep_device_list",
        "drivers/acpi/scan.c:acpi_bus_check_add",
        "drivers/acpi/scan.c:acpi_init_device_object",
        "drivers/acpi/scan.c:acpi_bus_get_acpi_device",
        "drivers/acpi/scan.c:acpi_bus_online",
        "drivers/acpi/scan.c:acpi_bus_offline"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585059072,
      "name": "acpi_get_device_data",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ➕</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
int acpi_get_device_data(acpi_handle handle, struct acpi_device * * device, void (*)(void *) callback)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
