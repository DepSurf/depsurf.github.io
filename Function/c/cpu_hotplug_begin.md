# Function: <code>cpu_hotplug_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void cpu_hotplug_begin()
```

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579374656,
      "name": "cpu_hotplug_begin",
      "external": true,
      "loc": "kernel/cpu.c:146",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_down",
        "kernel/cpu.c:_cpu_up",
        "drivers/acpi/acpi_processor.c:acpi_processor_add",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579374656,
      "name": "cpu_hotplug_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cpu_hotplug_begin()
```

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579387488,
      "name": "cpu_hotplug_begin",
      "external": true,
      "loc": "kernel/cpu.c:223",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579387488,
      "name": "cpu_hotplug_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
void cpu_hotplug_begin()
```

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579407872,
      "name": "cpu_hotplug_begin",
      "external": true,
      "loc": "kernel/cpu.c:289",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:_cpu_up",
        "kernel/cpu.c:_cpu_down",
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579407872,
      "name": "cpu_hotplug_begin",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 185
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584092368,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:124",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584363776,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:122",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584584770,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:126",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584682178,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:128",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584882285,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:130",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585018157,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585719679,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:141",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585842015,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:142",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585720847,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:147",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497428604,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584960621,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584869421,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584969741,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
  "name": "cpu_hotplug_begin",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585075917,
      "name": "cpu_hotplug_begin",
      "external": false,
      "loc": "include/linux/cpu.h:135",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpi_processor.c:acpi_processor_remove",
        "drivers/acpi/acpi_processor.c:acpi_processor_get_info"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void cpu_hotplug_begin()
```
</details>
</li>
</ul>
