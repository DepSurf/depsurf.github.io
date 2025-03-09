# Function: <code>acpi_fan_get_fst</code>

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
int acpi_fan_get_fst(struct acpi_device * device, struct acpi_fan_fst * fst)
```

```json
{
  "name": "acpi_fan_get_fst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_fan_get_fst",
      "external": true,
      "loc": "drivers/acpi/fan_core.c:78",
      "file": "drivers/acpi/fan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/fan_core.c:fan_get_cur_state",
        "drivers/acpi/fan_attr.c:show_fan_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594283576,
      "name": "acpi_fan_get_fst.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071587802800,
      "name": "acpi_fan_get_fst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 222
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
int acpi_fan_get_fst(struct acpi_device * device, struct acpi_fan_fst * fst)
```

```json
{
  "name": "acpi_fan_get_fst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589141216,
      "name": "acpi_fan_get_fst",
      "external": true,
      "loc": "drivers/acpi/fan_core.c:47",
      "file": "drivers/acpi/fan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/fan_core.c:fan_get_cur_state",
        "drivers/acpi/fan_attr.c:show_fan_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589141216,
      "name": "acpi_fan_get_fst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int acpi_fan_get_fst(struct acpi_device * device, struct acpi_fan_fst * fst)
```

```json
{
  "name": "acpi_fan_get_fst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589433568,
      "name": "acpi_fan_get_fst",
      "external": true,
      "loc": "drivers/acpi/fan_core.c:47",
      "file": "drivers/acpi/fan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/fan_core.c:fan_get_cur_state",
        "drivers/acpi/fan_attr.c:show_fan_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589433568,
      "name": "acpi_fan_get_fst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int acpi_fan_get_fst(struct acpi_device * device, struct acpi_fan_fst * fst)
```

```json
{
  "name": "acpi_fan_get_fst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589741488,
      "name": "acpi_fan_get_fst",
      "external": true,
      "loc": "drivers/acpi/fan_core.c:47",
      "file": "drivers/acpi/fan_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/fan_core.c:fan_get_cur_state",
        "drivers/acpi/fan_attr.c:show_fan_speed"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589741488,
      "name": "acpi_fan_get_fst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 262
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
int acpi_fan_get_fst(struct acpi_device * device, struct acpi_fan_fst * fst)
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
