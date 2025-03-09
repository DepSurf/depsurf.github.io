# Function: <code>acpi_scan_clear_dep</code>

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
int acpi_scan_clear_dep(struct acpi_dep_data * dep, void * data)
```

```json
{
  "name": "acpi_scan_clear_dep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586184208,
      "name": "acpi_scan_clear_dep",
      "external": false,
      "loc": "drivers/acpi/scan.c:2263",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_dev_clear_dependencies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586184208,
      "name": "acpi_scan_clear_dep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
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
int acpi_scan_clear_dep(struct acpi_dep_data * dep, void * data)
```

```json
{
  "name": "acpi_scan_clear_dep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587420000,
      "name": "acpi_scan_clear_dep",
      "external": false,
      "loc": "drivers/acpi/scan.c:2307",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_dev_clear_dependencies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587420000,
      "name": "acpi_scan_clear_dep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
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
int acpi_scan_clear_dep(struct acpi_dep_data * dep, void * data)
```

```json
{
  "name": "acpi_scan_clear_dep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588676880,
      "name": "acpi_scan_clear_dep",
      "external": false,
      "loc": "drivers/acpi/scan.c:2304",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_dev_clear_dependencies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588676880,
      "name": "acpi_scan_clear_dep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 210
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_scan_clear_dep(struct acpi_dep_data * dep, void * data)
```

```json
{
  "name": "acpi_scan_clear_dep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_scan_clear_dep",
      "external": false,
      "loc": "drivers/acpi/scan.c:2309",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_dev_clear_dependencies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964592,
      "name": "acpi_scan_clear_dep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 249
    },
    {
      "addr": 18446744071596745265,
      "name": "acpi_scan_clear_dep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int acpi_scan_clear_dep(struct acpi_dep_data * dep, void * data)
```

```json
{
  "name": "acpi_scan_clear_dep",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "acpi_scan_clear_dep",
      "external": false,
      "loc": "drivers/acpi/scan.c:2342",
      "file": "drivers/acpi/scan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/scan.c:acpi_dev_clear_dependencies"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589262032,
      "name": "acpi_scan_clear_dep",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 307
    },
    {
      "addr": 18446744071597653833,
      "name": "acpi_scan_clear_dep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
int acpi_scan_clear_dep(struct acpi_dep_data * dep, void * data)
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
