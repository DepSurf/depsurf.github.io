# Function: <code>disabled_by_idle_boot_param</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int disabled_by_idle_boot_param()
```

```json
{
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583745369,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:67",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug",
        "drivers/acpi/processor_idle.c:acpi_processor_cst_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583745369,
      "name": "disabled_by_idle_boot_param",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int disabled_by_idle_boot_param()
```

```json
{
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584069811,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:71",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584069811,
      "name": "disabled_by_idle_boot_param",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
int disabled_by_idle_boot_param()
```

```json
{
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584212359,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:72",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584212359,
      "name": "disabled_by_idle_boot_param",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584289285,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:72",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584686581,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:74",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584912756,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:74",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585016660,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:74",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585220323,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585356755,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586064435,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586186499,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586062435,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:59",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586555989,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:59",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587814373,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589156325,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:62",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589449525,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:62",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589757509,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:62",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 0,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:925",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "declared, inlined",
      "caller_inline": [],
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585158083,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585072243,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585308339,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
  "name": "disabled_by_idle_boot_param",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585414483,
      "name": "disabled_by_idle_boot_param",
      "external": false,
      "loc": "drivers/acpi/processor_idle.c:61",
      "file": "drivers/acpi/processor_idle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/processor_idle.c:acpi_processor_power_exit",
        "drivers/acpi/processor_idle.c:acpi_processor_power_init",
        "drivers/acpi/processor_idle.c:acpi_processor_power_state_has_changed",
        "drivers/acpi/processor_idle.c:acpi_processor_hotplug"
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
int disabled_by_idle_boot_param()
```
</details>
</li>
</ul>
