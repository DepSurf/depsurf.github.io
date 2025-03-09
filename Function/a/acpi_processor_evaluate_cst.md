# Function: <code>acpi_processor_evaluate_cst</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585716128,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:747",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585716128,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 875
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
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585838160,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:746",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585838160,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1180
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
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585717424,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:729",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585717424,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1182
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
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586198640,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:729",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586198640,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1237
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
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587435680,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:729",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_power_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587435680,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1250
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
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588694960,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:729",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588694960,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1250
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
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588982896,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:767",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588982896,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1241
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
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
```

```json
{
  "name": "acpi_processor_evaluate_cst",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589287072,
      "name": "acpi_processor_evaluate_cst",
      "external": true,
      "loc": "drivers/acpi/acpi_processor.c:810",
      "file": "drivers/acpi/acpi_processor.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/idle/intel_idle.c:intel_idle_acpi_cst_extract",
        "drivers/acpi/processor_idle.c:acpi_processor_get_cstate_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589287072,
      "name": "acpi_processor_evaluate_cst",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1241
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
int acpi_processor_evaluate_cst(acpi_handle handle, u32 cpu, struct acpi_processor_power * info)
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
