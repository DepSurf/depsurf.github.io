# Function: <code>acpi_power_resource_add_dependent</code>

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
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584920475,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:242",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585056283,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:242",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_power_resource_add_dependent(struct acpi_power_resource * resource, struct device * dev)
```

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585759808,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:240",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585759808,
      "name": "acpi_power_resource_add_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
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
int acpi_power_resource_add_dependent(struct acpi_power_resource * resource, struct device * dev)
```

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585878896,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:240",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585878896,
      "name": "acpi_power_resource_add_dependent",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 217
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585755889,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:238",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586238641,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:249",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587477889,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:249",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588745582,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:249",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589033966,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:250",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589338522,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:250",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497462452,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:242",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584987147,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:242",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584902731,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:242",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585007867,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:242",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_power_resource_add_dependent",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585114043,
      "name": "acpi_power_resource_add_dependent",
      "external": false,
      "loc": "drivers/acpi/power.c:242",
      "file": "drivers/acpi/power.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/power.c:acpi_device_power_add_dependent"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
int acpi_power_resource_add_dependent(struct acpi_power_resource * resource, struct device * dev)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
int acpi_power_resource_add_dependent(struct acpi_power_resource * resource, struct device * dev)
```
</details>
</li>
</ul>
