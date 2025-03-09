# Function: <code>acpi_ds_resolve_package_element</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584436301,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:349",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
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
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584659951,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:355",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584759742,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584962229,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585098029,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585802677,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585802677,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585923499,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585923499,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 717
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
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585800749,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585800749,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586286435,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586286435,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 738
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
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587530869,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587530869,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 776
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
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588809136,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588809136,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 849
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
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589098608,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589098608,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
```

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589404352,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589404352,
      "name": "acpi_ds_resolve_package_element",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 854
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336497493148,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
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
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585017832,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
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
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584933465,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/acpi/acpica/dspkginit.c:acpi_ds_init_package_element"
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
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585049613,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
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
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "acpi_ds_resolve_package_element",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585155773,
      "name": "acpi_ds_resolve_package_element",
      "external": false,
      "loc": "drivers/acpi/acpica/dspkginit.c:381",
      "file": "drivers/acpi/acpica/dspkginit.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void acpi_ds_resolve_package_element(union acpi_operand_object * * element_ptr)
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
