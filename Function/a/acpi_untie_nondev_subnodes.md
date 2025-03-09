# Function: <code>acpi_untie_nondev_subnodes</code>

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
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_untie_nondev_subnodes(struct acpi_device_data * data)
```

```json
{
  "name": "acpi_untie_nondev_subnodes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588769845,
      "name": "acpi_untie_nondev_subnodes",
      "external": false,
      "loc": "drivers/acpi/property.c:355",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_free_properties"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_free_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588768096,
      "name": "acpi_untie_nondev_subnodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_untie_nondev_subnodes(struct acpi_device_data * data)
```

```json
{
  "name": "acpi_untie_nondev_subnodes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589058869,
      "name": "acpi_untie_nondev_subnodes",
      "external": false,
      "loc": "drivers/acpi/property.c:355",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_free_properties"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_free_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589057120,
      "name": "acpi_untie_nondev_subnodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void acpi_untie_nondev_subnodes(struct acpi_device_data * data)
```

```json
{
  "name": "acpi_untie_nondev_subnodes",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589364229,
      "name": "acpi_untie_nondev_subnodes",
      "external": false,
      "loc": "drivers/acpi/property.c:359",
      "file": "drivers/acpi/property.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/property.c:acpi_free_properties"
      ],
      "caller_func": [
        "drivers/acpi/property.c:acpi_free_properties",
        "drivers/acpi/property.c:acpi_init_properties"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589360720,
      "name": "acpi_untie_nondev_subnodes",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 816
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
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void acpi_untie_nondev_subnodes(struct acpi_device_data * data)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
