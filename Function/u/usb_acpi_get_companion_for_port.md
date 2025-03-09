# Function: <code>usb_acpi_get_companion_for_port</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587044720,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:143",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587044720,
      "name": "usb_acpi_get_companion_for_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587245120,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:143",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587245120,
      "name": "usb_acpi_get_companion_for_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588098992,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:144",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588098992,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588140880,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:144",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/usb/core/usb-acpi.c:usb_acpi_find_companion_for_port"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588140880,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588022976,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:144",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588022976,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588639232,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:144",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588639232,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 254
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
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590055648,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:144",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590055648,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 266
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
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591662496,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:193",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591662496,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592084928,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:189",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592084928,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592825360,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:189",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592825360,
      "name": "usb_acpi_get_companion_for_port",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 150
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336500344120,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:143",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500344120,
      "name": "usb_acpi_get_companion_for_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 260
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
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586951200,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:143",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586951200,
      "name": "usb_acpi_get_companion_for_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586892352,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:143",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586892352,
      "name": "usb_acpi_get_companion_for_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587199680,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:143",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587199680,
      "name": "usb_acpi_get_companion_for_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "usb_acpi_get_companion_for_port",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587306752,
      "name": "usb_acpi_get_companion_for_port",
      "external": false,
      "loc": "drivers/usb/core/usb-acpi.c:143",
      "file": "drivers/usb/core/usb-acpi.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587306752,
      "name": "usb_acpi_get_companion_for_port.isra.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 236
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
struct acpi_device * usb_acpi_get_companion_for_port(struct usb_port * port_dev)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
