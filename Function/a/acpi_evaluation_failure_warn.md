# Function: <code>acpi_evaluation_failure_warn</code>

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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void acpi_evaluation_failure_warn(acpi_handle handle, const char * name, acpi_status status)
```

```json
{
  "name": "acpi_evaluation_failure_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585672768,
      "name": "acpi_evaluation_failure_warn",
      "external": true,
      "loc": "drivers/acpi/utils.c:520",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585672768,
      "name": "acpi_evaluation_failure_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void acpi_evaluation_failure_warn(acpi_handle handle, const char * name, acpi_status status)
```

```json
{
  "name": "acpi_evaluation_failure_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586152336,
      "name": "acpi_evaluation_failure_warn",
      "external": true,
      "loc": "drivers/acpi/utils.c:534",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_info",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586152336,
      "name": "acpi_evaluation_failure_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 60
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
void acpi_evaluation_failure_warn(acpi_handle handle, const char * name, acpi_status status)
```

```json
{
  "name": "acpi_evaluation_failure_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587385264,
      "name": "acpi_evaluation_failure_warn",
      "external": true,
      "loc": "drivers/acpi/utils.c:534",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587385264,
      "name": "acpi_evaluation_failure_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void acpi_evaluation_failure_warn(acpi_handle handle, const char * name, acpi_status status)
```

```json
{
  "name": "acpi_evaluation_failure_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588634960,
      "name": "acpi_evaluation_failure_warn",
      "external": true,
      "loc": "drivers/acpi/utils.c:572",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588634960,
      "name": "acpi_evaluation_failure_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void acpi_evaluation_failure_warn(acpi_handle handle, const char * name, acpi_status status)
```

```json
{
  "name": "acpi_evaluation_failure_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588922704,
      "name": "acpi_evaluation_failure_warn",
      "external": true,
      "loc": "drivers/acpi/utils.c:572",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588922704,
      "name": "acpi_evaluation_failure_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void acpi_evaluation_failure_warn(acpi_handle handle, const char * name, acpi_status status)
```

```json
{
  "name": "acpi_evaluation_failure_warn",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589221760,
      "name": "acpi_evaluation_failure_warn",
      "external": true,
      "loc": "drivers/acpi/utils.c:644",
      "file": "drivers/acpi/utils.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/pci_link.c:acpi_pci_link_set",
        "drivers/acpi/pci_link.c:acpi_pci_link_get_current",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_tsd",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_states",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_throttling_control",
        "drivers/acpi/processor_throttling.c:acpi_processor_get_platform_limit",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_states",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_performance_control",
        "drivers/acpi/processor_perflib.c:acpi_processor_get_platform_limit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589221760,
      "name": "acpi_evaluation_failure_warn",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 75
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
void acpi_evaluation_failure_warn(acpi_handle handle, const char * name, acpi_status status)
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
