# Function: <code>acpi_notify_device</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_notify_device(acpi_handle handle, u32 event, void * data)
```

```json
{
  "name": "acpi_notify_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586173365,
      "name": "acpi_notify_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:501",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_notify_device_fixed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586173312,
      "name": "acpi_notify_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 33
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
void acpi_notify_device(acpi_handle handle, u32 event, void * data)
```

```json
{
  "name": "acpi_notify_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587408197,
      "name": "acpi_notify_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:538",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_notify_device_fixed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587408144,
      "name": "acpi_notify_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 45
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
void acpi_notify_device(acpi_handle handle, u32 event, void * data)
```

```json
{
  "name": "acpi_notify_device",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588662981,
      "name": "acpi_notify_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:543",
      "file": "drivers/acpi/bus.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/bus.c:acpi_notify_device_fixed"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588662912,
      "name": "acpi_notify_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void acpi_notify_device(acpi_handle handle, u32 event, void * data)
```

```json
{
  "name": "acpi_notify_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588950896,
      "name": "acpi_notify_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:522",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588950896,
      "name": "acpi_notify_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void acpi_notify_device(acpi_handle handle, u32 event, void * data)
```

```json
{
  "name": "acpi_notify_device",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589247520,
      "name": "acpi_notify_device",
      "external": false,
      "loc": "drivers/acpi/bus.c:548",
      "file": "drivers/acpi/bus.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589247520,
      "name": "acpi_notify_device",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 42
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
void acpi_notify_device(acpi_handle handle, u32 event, void * data)
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
