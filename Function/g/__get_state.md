# Function: <code>__get_state</code>

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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
int __get_state(acpi_handle handle, u8 * state)
```

```json
{
  "name": "__get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586237312,
      "name": "__get_state",
      "external": false,
      "loc": "drivers/acpi/power.c:186",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_power_get_inferred_state",
        "drivers/acpi/power.c:acpi_power_wakeup_list_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586237312,
      "name": "__get_state",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int __get_state(acpi_handle handle, u8 * state)
```

```json
{
  "name": "__get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587476192,
      "name": "__get_state",
      "external": false,
      "loc": "drivers/acpi/power.c:186",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_power_get_inferred_state",
        "drivers/acpi/power.c:acpi_power_wakeup_list_init",
        "drivers/acpi/power.c:acpi_power_get_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587476192,
      "name": "__get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int __get_state(acpi_handle handle, u8 * state)
```

```json
{
  "name": "__get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588743792,
      "name": "__get_state",
      "external": false,
      "loc": "drivers/acpi/power.c:186",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_get_inferred_state",
        "drivers/acpi/power.c:acpi_power_wakeup_list_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588743792,
      "name": "__get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int __get_state(acpi_handle handle, u8 * state)
```

```json
{
  "name": "__get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589032176,
      "name": "__get_state",
      "external": false,
      "loc": "drivers/acpi/power.c:187",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_get_inferred_state",
        "drivers/acpi/power.c:acpi_power_wakeup_list_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589032176,
      "name": "__get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int __get_state(acpi_handle handle, u8 * state)
```

```json
{
  "name": "__get_state",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589336736,
      "name": "__get_state",
      "external": false,
      "loc": "drivers/acpi/power.c:187",
      "file": "drivers/acpi/power.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/power.c:acpi_resume_power_resources",
        "drivers/acpi/power.c:acpi_add_power_resource",
        "drivers/acpi/power.c:acpi_power_get_inferred_state",
        "drivers/acpi/power.c:acpi_power_wakeup_list_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589336736,
      "name": "__get_state",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 181
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
int __get_state(acpi_handle handle, u8 * state)
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
