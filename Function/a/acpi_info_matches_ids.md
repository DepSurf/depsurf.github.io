# Function: <code>acpi_info_matches_ids</code>

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
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_info_matches_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585826152,
      "name": "acpi_info_matches_ids",
      "external": false,
      "loc": "drivers/acpi/scan.c:755",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_check_dep"
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
  "name": "acpi_info_matches_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585705002,
      "name": "acpi_info_matches_ids",
      "external": false,
      "loc": "drivers/acpi/scan.c:756",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_check_dep"
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
  "name": "acpi_info_matches_ids",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586186070,
      "name": "acpi_info_matches_ids",
      "external": false,
      "loc": "drivers/acpi/scan.c:764",
      "file": "drivers/acpi/scan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/scan.c:acpi_scan_check_dep"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
bool acpi_info_matches_ids(struct acpi_device_info * info, const const char * * ids)
```

```json
{
  "name": "acpi_info_matches_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587417712,
      "name": "acpi_info_matches_ids",
      "external": false,
      "loc": "drivers/acpi/scan.c:782",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587417712,
      "name": "acpi_info_matches_ids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool acpi_info_matches_ids(struct acpi_device_info * info, const const char * * ids)
```

```json
{
  "name": "acpi_info_matches_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588674448,
      "name": "acpi_info_matches_ids",
      "external": false,
      "loc": "drivers/acpi/scan.c:760",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588674448,
      "name": "acpi_info_matches_ids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool acpi_info_matches_ids(struct acpi_device_info * info, const const char * * ids)
```

```json
{
  "name": "acpi_info_matches_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588962176,
      "name": "acpi_info_matches_ids",
      "external": false,
      "loc": "drivers/acpi/scan.c:759",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588962176,
      "name": "acpi_info_matches_ids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool acpi_info_matches_ids(struct acpi_device_info * info, const const char * * ids)
```

```json
{
  "name": "acpi_info_matches_ids",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589259616,
      "name": "acpi_info_matches_ids",
      "external": false,
      "loc": "drivers/acpi/scan.c:759",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_scan_check_dep",
        "drivers/acpi/scan.c:acpi_scan_check_dep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589259616,
      "name": "acpi_info_matches_ids",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 168
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
bool acpi_info_matches_ids(struct acpi_device_info * info, const const char * * ids)
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
